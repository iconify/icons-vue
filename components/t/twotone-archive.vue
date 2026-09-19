<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5ulj5mwy"/><path class="itjwo7y1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-archive" /></template>
<style>
.itjwo7y1h {
  fill: currentColor;
  d: path("M16 13h-2.55v-3h-2.9v3H8l4 4zm4.54-7.77l-1.39-1.68C18.88 3.21 18.47 3 18 3H6c-.47 0-.88.21-1.16.55L3.46 5.23C3.17 5.57 3 6.02 3 6.5V19c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V6.5c0-.48-.17-.93-.46-1.27M6.24 5h11.52l.81.97H5.44zM19 19H5V8h14z");
}

.o5ulj5mwy {
  fill: currentColor;
  d: path("M5 19h14V8H5zm5.55-6v-3h2.91v3H16l-4 4l-4-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
