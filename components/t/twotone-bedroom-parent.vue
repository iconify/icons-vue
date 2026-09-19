<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fakvs-b8p"/><path class="q-udmo56r"/><path class="geuilwfwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-bedroom-parent" /></template>
<style>
.fakvs-b8p {
  fill: currentColor;
  d: path("M4 20h16V4H4zm1-6.83c0-.66.25-1.26.65-1.72V9c0-1.1.9-2 2-2H11c.37 0 .72.12 1 .32c.28-.2.63-.32 1-.32h3.35c1.1 0 2 .9 2 2v2.45c.4.46.65 1.06.65 1.72V17h-1.5v-1.5h-11V17H5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.geuilwfwo {
  fill: currentColor;
  d: path("M6.5 15.5h11V17H19v-3.83c0-.66-.25-1.26-.65-1.72V9c0-1.1-.9-2-2-2H13c-.37 0-.72.12-1 .32c-.28-.2-.63-.32-1-.32H7.65c-1.1 0-2 .9-2 2v2.45c-.4.46-.65 1.06-.65 1.72V17h1.5zm6.25-7h4v2h-4zm-5.5 0h4v2h-4zM6.5 13c0-.55.45-1 1-1h9c.55 0 1 .45 1 1v1h-11z");
}

.q-udmo56r {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 18H4V4h16z");
}

</style>
