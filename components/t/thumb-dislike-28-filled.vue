<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="b6ortjb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:thumb-dislike-28-filled" /></template>
<style>
.b6ortjb5d {
  fill: currentColor;
  d: path("M14.874 2.234a6.5 6.5 0 0 1 8.11 5.096l.946 5.156a4.25 4.25 0 0 1-4.18 5.016h-1.5c.057.287.122.626.187.99c.185 1.043.382 2.36.382 3.296c0 1.786-.612 2.936-1.29 3.643a3.9 3.9 0 0 1-.922.713a3 3 0 0 1-.46.206l-.018.006c-1.18.466-2.46-.287-2.759-1.45c-.686-2.671-2.644-7.952-7.652-10.563c-1.564-.816-2.746-2.529-2.411-4.434l.42-2.396a3.75 3.75 0 0 1 2.704-2.967z");
}

</style>
