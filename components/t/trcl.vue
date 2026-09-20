<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGj7FEBdXc)" class="q3_b1ib8j"/><defs><linearGradient id="SVGj7FEBdXc" x1="3.736" x2="20.411" y1="8.824" y2="9.353" gradientUnits="userSpaceOnUse"><stop class="i45z-924x"/><stop offset="1" class="ngq20kxei"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trcl" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i45z-924x {
  stop-color: var(--svg-color--101bab, #101bab);
}

.ngq20kxei {
  stop-color: var(--svg-color--111b38, #111b38);
}

.q3_b1ib8j {
  d: path("M4.323 11.206L3 12.266C3 8.558 5.615 3.53 11.438 3.53c3.023 0 5.23 1.16 6.882 2.753l.503-.1l-.275.333A8.95 8.95 0 0 1 21 12.8c0 4.023-1.233 6.786-1.853 7.67c-2.911-1.058-3.44-3.705-3.44-4.764c0-.604.163-1.043.349-1.52c.211-.56.428-1.127.428-2.186c0-.53-.116-1.852-.915-3.213L10.41 12.72v.08a2.382 2.382 0 1 1-1.397-2.17l5.892-2.753c-.868-.953-2.234-1.7-4.262-1.7c-4.235 0-5.966 3.357-6.32 5.03");
}

</style>
