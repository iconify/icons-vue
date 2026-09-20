<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mumfproca"/><path clip-rule="evenodd" class="v2hw23h9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:scrt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.v2hw23h9k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10.87 9.219c-2.56-1.286-1.706-4.148 1.068-4.148c3.077 0 5.12 1.928 5.547 2.571l.64-.643C16.845 5.285 14.711 4 11.938 4c-1.089 0-2.302.275-3.222.744c-1.948.993-4.137 4.56-1.259 6.832c1.22.963 2.719 1.643 4.052 2.249c1.87.849 3.416 1.55 3.416 2.678c0 1.928-4.716 3.835-8.322.214l-.853.429c1.345 1.35 3.084 2.273 4.201 2.61c1.118.339 2.965.31 4.201 0c2.465-.618 4.441-2.629 4.048-4.958c-.455-2.69-3.154-3.806-5.533-4.79c-.638-.263-1.254-.517-1.796-.789M8.525 6.005C7.48 6.729 6.39 9.53 8.31 10.932c.79.578 1.931 1.07 3.098 1.572c1.986.857 4.048 1.745 4.584 3.142c.414 1.08-.427 2.357-.427 2.357s2.242-1.322 1.494-3.428c-.618-1.738-2.517-2.514-4.422-3.292c-1.385-.566-2.773-1.133-3.674-2.073c-1.436-1.497-.439-3.205-.439-3.205");
}

</style>
