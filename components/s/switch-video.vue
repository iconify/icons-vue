<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5huz97yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-video" /></template>
<style>
.a5huz97yv {
  fill: currentColor;
  d: path("m7.98 14.808l.709-.708l-1.6-1.6h6.784l-1.6 1.6l.708.708L15.788 12l-2.807-2.808l-.708.708l1.6 1.6H7.089l1.6-1.6l-.708-.708L5.173 12zM5.097 19q-.69 0-1.153-.462t-.462-1.153V6.615q0-.69.462-1.152T5.096 5h10.77q.69 0 1.152.463t.463 1.153v4.653l3.038-3.038v7.538l-3.038-3.038v4.654q0 .69-.463 1.153T15.866 19z");
}

</style>
