<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":253};
const content = `<defs><path id="SVG372KxeZZ" class="x2qg58-eq"/><path id="SVGpakb87il" class="kncvcufyy"/><filter id="SVGXuWGNe6h" width="181.4%" height="132.2%" x="-40.2%" y="-14.9%" filterUnits="objectBoundingBox"><feMorphology in="SourceAlpha" operator="dilate" radius="2" result="shadowSpreadOuter1"/><feOffset dy="2" in="shadowSpreadOuter1" result="shadowOffsetOuter1"/><feGaussianBlur in="shadowOffsetOuter1" result="shadowBlurOuter1" stdDeviation="3"/><feColorMatrix in="shadowBlurOuter1" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.3 0"/></filter></defs><mask id="SVGWMiDveth" class="n1mjunbsu"><use href="#SVGpakb87il"/></mask><path mask="url(#SVGWMiDveth)" class="xjub1hb-m"/><g mask="url(#SVGWMiDveth)"><use filter="url(#SVGXuWGNe6h)" href="#SVG372KxeZZ"/></g><path mask="url(#SVGWMiDveth)" class="n2ryc8d2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:vlang" /></template>
<style>
.kncvcufyy {
  d: path("m5.614.039l68.178 6.568c4.325.417 9.001 4.084 10.437 8.185l43.851 125.291l43.638-125.287c1.397-4.014 5.899-7.613 10.142-8.158l.283-.031L250.32.039c4.326-.417 6.643 2.564 5.173 6.653l-86.696 241.083l-.413 1.147c-.47 1.308-1.605 2.458-2.93 3.117c-.483.372-1.136.587-1.919.587h-66.78q-.124 0-.246-.003l.246.003a9 9 0 0 1-.493-.014c-4.203-.237-8.629-3.459-10.043-7.394L.442 6.692c-1.47-4.089.847-7.07 5.172-6.653");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n2ryc8d2o {
  fill: var(--svg-color--5d87bf, #5d87bf);
  d: path("m5.614.039l68.178 6.568c4.325.417 9.001 4.084 10.437 8.185l81.943 234.12c.717 2.05-.464 3.714-2.637 3.714h-66.78c-4.345 0-9.066-3.319-10.536-7.408L.442 6.692c-1.47-4.089.847-7.07 5.172-6.653");
}

.x2qg58-eq {
  fill: var(--svg-color--000, #000);
  d: path("m158.907 248.922l-36.096-104.274l5.156-3.223l36.741 106.35z");
}

.xjub1hb-m {
  fill: var(--svg-color--536b8a, #536b8a);
  d: path("M168.797 247.775L255.493 6.692c1.47-4.089-.847-7.07-5.173-6.653l-68.177 6.568c-4.325.417-8.997 4.086-10.425 8.189L91.473 245.193c-1.43 4.102.937 7.433 5.282 7.433h66.36c2.173 0 4.534-1.659 5.269-3.704z");
}

</style>
