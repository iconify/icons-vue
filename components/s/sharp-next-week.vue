<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpvsqo9me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-next-week" /></template>
<style>
.zpvsqo9me {
  fill: currentColor;
  d: path("M22 7h-6V5c0-.55-.22-1.05-.59-1.41C15.05 3.22 14.55 3 14 3h-4c-1.1 0-2 .9-2 2v2H2v15h20zM10 5h4v2h-4zm1 13.5l-1-1l3-3l-3-3l1-1l4 4z");
}

</style>
