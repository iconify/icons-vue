<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn2jjdh3z"/><path class="fvh9nhkgm"/><path class="xn2aubb4f"/><path class="llimd__ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sd" /></template>
<style>
.fvh9nhkgm {
  fill: currentColor;
  d: path("M14.5 10.5h2v3h-2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.llimd__ue {
  fill: currentColor;
  d: path("M20 4H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14H4V6h16z");
}

.nn2jjdh3z {
  fill: currentColor;
  d: path("M4 18h16V6H4zm9-9h4c.55 0 1 .45 1 1v4c0 .55-.45 1-1 1h-4zm-7 4h1.5v.5h2v-1H7c-.55 0-1-.45-1-1V10c0-.55.45-1 1-1h3c.55 0 1 .45 1 1v1H9.5v-.5h-2v1H10c.55 0 1 .45 1 1V14c0 .55-.45 1-1 1H7c-.55 0-1-.45-1-1z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.xn2aubb4f {
  fill: currentColor;
  d: path("M7 15h3c.55 0 1-.45 1-1v-1.5c0-.55-.45-1-1-1H7.5v-1h2v.5H11v-1c0-.55-.45-1-1-1H7c-.55 0-1 .45-1 1v1.5c0 .55.45 1 1 1h2.5v1h-2V13H6v1c0 .55.45 1 1 1m11-1v-4c0-.55-.45-1-1-1h-4v6h4c.55 0 1-.45 1-1m-1.5-.5h-2v-3h2z");
}

</style>
