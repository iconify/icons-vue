<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGDoNhQdyS)" class="kdi0a1q6w"/><defs><linearGradient id="SVGDoNhQdyS" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="dbvqxqbzl"/><stop offset="1" class="jg-xypbyg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:source" /></template>
<style>
.dbvqxqbzl {
  stop-color: var(--svg-color--ed69ff, #ed69ff);
}

.ft5dv1b6b {
  fill: none;
}

.jg-xypbyg {
  stop-color: var(--svg-color--7b61f4, #7b61f4);
}

.kdi0a1q6w {
  d: path("M11.87 11.539c-.81-.715-2.43-2.38-2.43-3.308c0-1.159 1.216-1.856 3.123-1.856c.708 0 1.237.568 1.957 1.339l.495.517c.99 1.018 1.277 1.153 2.076 1.153c.798 0 1.659-.298 1.659-2.278C18.75 5.115 15.662 3 11.87 3C8.086 3 5.25 6.037 5.25 8.062c0 2.037 2.812 4.04 6.62 3.477m.26.922c.81.715 2.43 2.38 2.43 3.308c0 1.158-2.127 1.687-2.982 1.687s-1.603-.675-2.593-1.687c-.99-1.018-1.277-1.153-2.076-1.153c-.798 0-1.659.298-1.659 2.278c0 1.99 3.088 4.106 6.88 4.106c3.785 0 6.62-3.038 6.62-5.063c0-2.036-2.812-4.038-6.62-3.476");
}

</style>
