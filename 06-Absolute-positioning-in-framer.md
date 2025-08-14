# 🧠 Absolute Positioning in Framer

Absolute positioning in Framer is a powerful tool for controlling the precise placement of layers within your designs. Unlike standard flow, it gives you the freedom to move elements without affecting their neighbors.

---

## 📌 What is Absolute Positioning?

- **Definition:** Position a layer relative to its **parent frame**. Think of it as a floating object. you can place it anywhere inside its container.
- **Floating Layers:** Layers set to absolute "float" above other layers. Moving them does not disturb sibling layers.

---

## 📍 Pinning: Your Positioning Compass

- **Pinning** describes a layer's position relative to edges (top, bottom, left, right) of its parent.
- **Importance:** Pinned layers maintain their position when the parent frame resizes.
- **Unpinning** allows flexible spacing as the parent frame changes.
- **How to pin:** Set a value or use the pinning controls in the properties panel.

---

## 🖼️ Absolute Positioning within Stacks

- Stacks organize layers in a flow, but you can override this by setting a layer to **absolute**.
- Absolute layers in stacks are removed from the stack flow; siblings behave as if it’s not there.
- Useful for unique layouts like overlapping elements that stacks alone cannot handle.

---

## 🔢 Z-Index: Controlling Layer Order

- **Definition:** **Z-index** controls the vertical stacking order of layers.
- **How it works:** Higher z-index layers appear in front of lower ones.
- **Default:** All layers have a default z-index of 0.
- **Purpose:** Gives precise control over overlapping elements, independent of layer hierarchy.
