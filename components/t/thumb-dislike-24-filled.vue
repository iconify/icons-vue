<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2tkb6bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thumb-dislike-24-filled" /></template>
<style>
.u2tkb6bbh {
  fill: currentColor;
  d: path("M12.534 2.209a5.75 5.75 0 0 1 7.193 4.504l.709 3.861a3.75 3.75 0 0 1-3.69 4.427h-.941c.04.211.085.45.13.702c.154.88.322 2.001.322 2.797c0 1.503-.46 2.477-.998 3.083a3 3 0 0 1-.743.61a2 2 0 0 1-.359.168l-.05.017c-1.06.405-2.196-.261-2.484-1.29c-.615-2.198-2.322-6.522-6.494-8.674c-1.354-.698-2.382-2.19-2.074-3.853l.356-1.925a3.25 3.25 0 0 1 2.326-2.541z");
}

</style>
