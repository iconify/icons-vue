<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tjvqvqi7f"/><path class="kxclo-b8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:school-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kxclo-b8r {
  d: path("m3.553 6.105l6-2.999a5.47 5.47 0 0 1 4.894 0l6 2.999c.236.119.416.325.501.576l.001.002a1.001 1.001 0 0 1-1.396 1.212l-.889-.444l-.027-.014l-5.084-2.543a3.48 3.48 0 0 0-3.106 0L5.363 7.437l-.027.014l-.889.443a1 1 0 1 1-.894-1.788ZM9 10a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M9 21v-3a3 3 0 1 1 6 0v3a1 1 0 0 1-2 0v-3a1 1 0 0 0-2 0v3a1 1 0 0 1-2 0");
}

.tjvqvqi7f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m5.553 5.106l4-2a5.47 5.47 0 0 1 4.894 0l4 2A1 1 0 0 1 19 6v4.465l2.555 1.703A1 1 0 0 1 22 13v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5v-4a1 1 0 0 1 .445-.832L5 10.465V6c0-.379.214-.725.553-.894");
}

</style>
