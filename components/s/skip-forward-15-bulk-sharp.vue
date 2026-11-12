<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j8-zxbb8n"/><path class="kez1eum_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-forward-15-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j8-zxbb8n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.293 12.293A1 1 0 0 1 9 13v8a1 1 0 0 1-2 0v-5.586l-.293.293a.999.999 0 1 1-1.414-1.414ZM13 14v2h1c.511 0 1.025-.001 1.535.033c1.064.071 2.219.308 2.911 1.197c.393.506.554 1.137.554 1.77s-.161 1.264-.554 1.77c-.692.889-1.847 1.126-2.911 1.197c-.51.034-1.024.033-1.535.033h-2a1 1 0 0 1 0-2h2c.467 0 .936.002 1.402-.029c.38-.025 1.204-.094 1.465-.429c.116-.149.133-.36.133-.542c0-.462-.13-.656-.566-.801c-.331-.11-.686-.147-1.032-.17C14.936 17.998 14.467 18 14 18h-2a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h6a1 1 0 0 1 0 2Z");
}

.kez1eum_x {
  d: path("M19 4.937V4a1 1 0 0 1 2 0v4a.997.997 0 0 1-1 1h-4a1 1 0 0 1 0-2h2.174a7.943 7.943 0 0 0-13.28 1.447a1 1 0 1 1-1.788-.894A9.937 9.937 0 0 1 19 4.937");
}

</style>
