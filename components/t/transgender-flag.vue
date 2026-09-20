<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="hlwq5_ryo"/><path class="r90vrxjju"/><path class="gyy9svbvz"/><path class="hy9buccok"/><path class="z1eqssbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:transgender-flag" /></template>
<style>
.gyy9svbvz {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 15.3h36v5.3H0z");
}

.hlwq5_ryo {
  fill: var(--svg-color--5bcefa, #5bcefa);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-1.3H0z");
}

.hy9buccok {
  fill: var(--svg-color--f5a9b8, #f5a9b8);
  d: path("M0 9.902h36V15.4H0z");
}

.r90vrxjju {
  fill: var(--svg-color--f5a9b8, #f5a9b8);
  d: path("M.026 20.5L0 25.8h36v-5.3z");
}

.z1eqssbjl {
  fill: var(--svg-color--5bcefa, #5bcefa);
  d: path("M36 9a4 4 0 0 0-4-4H4a4 4 0 0 0-4 4v1.2h36z");
}

</style>
