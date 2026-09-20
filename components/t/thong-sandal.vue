<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="j0pgkbcaz"/><path class="zndgiobrl"/><path class="p33regbuz"/><path class="hs1dnum8u"/><path class="jsdvaibxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:thong-sandal" /></template>
<style>
.hs1dnum8u {
  fill: var(--svg-color--269, #269);
  d: path("M18.823 8.394c3.583.695 5.602 3.551 6.128 7.201c.506 3.505-2.122 7.645-2.775 7.614c-1.375-.066 2.149-4.571-.039-8.286c-1.603-2.723-2.518-2.064-3.531-3.707c-1.189 1.147-2.703.279-4.272 2.386c-2.417 3.248.444 7.011-.57 7.367c-.777.273-3.091-5.844-1.337-9.337c1.685-3.356 6.396-3.238 6.396-3.238");
}

.j0pgkbcaz {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M19.5 1.299c7.253 1.456 8.185 11.081 5.258 18.46c-2.516 6.344-3.042 14.215-7.231 14.965c-5.506.985-8.05-3.674-6.279-11.312c1.176-5.07.265-9.632.279-14.707c.014-4.797 3.261-8.352 7.973-7.406");
}

.jsdvaibxd {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M18.823 8.394c3.583.695 5.602 3.551 6.128 7.201c.506 3.505-2.008 7.464-2.661 7.44c-1.209-.045 2.238-4.432.358-8.236c-1.4-2.833-3.357-2.417-3.984-4.208c-1.253 1.611-3.402.269-4.834 2.82c-1.982 3.53.537 7.073-.179 7.386c-.754.33-2.979-5.671-1.224-9.165c1.685-3.356 6.396-3.238 6.396-3.238");
}

.p33regbuz {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M19.254 5.332c1.672.283.065 3.213-.052 4.364c-.118 1.151-.622 1.57-.716-.134c-.09-1.611-1.252-4.572.768-4.23");
}

.zndgiobrl {
  fill: var(--svg-color--269, #269);
  d: path("M19.254 5.332c1.672.283.518 3.836.4 4.987s-1.769 1.107-1.667-.597s-.753-4.732 1.267-4.39");
}

</style>
