<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eq9oz0fyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-edit-20-filled" /></template>
<style>
.eq9oz0fyv {
  fill: currentColor;
  d: path("M10.898 2.9a1 1 0 0 0-1.794 0l-1.93 3.91l-4.317.628a1 1 0 0 0-.554 1.706l3.124 3.044l-.738 4.3a1 1 0 0 0 1.451 1.054l3.426-1.801c.16-.4.4-.764.707-1.07l4.829-4.83a2.87 2.87 0 0 1 2.665-.77a1 1 0 0 0-.622-1.633l-4.317-.627zm4.911 7.648l-4.83 4.83a2.2 2.2 0 0 0-.577 1.02l-.375 1.498a.89.89 0 0 0 1.079 1.079l1.498-.375a2.2 2.2 0 0 0 1.02-.578l4.83-4.83a1.87 1.87 0 0 0-2.645-2.644");
}

</style>
