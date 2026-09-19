<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au5baebrb"/><path class="l9m0s9beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-notifications-off" /></template>
<style>
.au5baebrb {
  fill: currentColor;
  d: path("M8 17h8v-.24L8.34 9.1C8.12 9.68 8 10.32 8 11zm4-10.5c-.19 0-.37.03-.55.06L16 11.1V11c0-2.48-1.51-4.5-4-4.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.l9m0s9beg {
  fill: currentColor;
  d: path("M12 22c1.1 0 2-.9 2-2h-4c0 1.1.9 2 2 2m0-15.5c2.49 0 4 2.02 4 4.5v.1l2 2V11c0-3.07-1.63-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68c-.24.06-.47.15-.69.23l1.64 1.64c.18-.02.36-.05.55-.05M5.41 3.35L4 4.76l2.81 2.81C6.29 8.57 6 9.74 6 11v5l-2 2v1h14.24l1.74 1.74l1.41-1.41zM16 17H8v-6c0-.68.12-1.32.34-1.9L16 16.76z");
}

</style>
