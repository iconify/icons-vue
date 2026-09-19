<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp37kwg-z"/><path class="yn4p49bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-missed-video-call" /></template>
<style>
.tp37kwg-z {
  fill: currentColor;
  d: path("M15 13.5V8H5v8h10zM11 15l-3.89-3.89v2.55H6V9.22h4.44v1.11H7.89l3.11 3.1l2.99-3.01l.78.79z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yn4p49bte {
  fill: currentColor;
  d: path("M3 17c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11l-4 4V7c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1zm2-9h10v8H5zm6 5.43l-3.11-3.1h2.55V9.22H6v4.44h1.11v-2.55L11 15l3.77-3.79l-.78-.79z");
}

</style>
