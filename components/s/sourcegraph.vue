<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":262};
const content = `<path class="lj6o8abyb"/><path class="bnus8tbil"/><path class="t3kxshl8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:sourcegraph" /></template>
<style>
.bnus8tbil {
  fill: var(--svg-color--b200f8, #b200f8);
  d: path("M179.662 32.813L37.046 193.858c-9.621 10.86-8.616 27.464 2.233 37.087c10.85 9.62 27.438 8.617 37.059-2.238L218.954 67.665c9.621-10.86 8.616-27.459-2.233-37.083c-10.854-9.63-27.446-8.624-37.059 2.23z");
}

.lj6o8abyb {
  fill: var(--svg-color--f96316, #f96316);
  d: path("m74.203 33.602l56.952 208.194c3.827 13.991 18.27 22.23 32.254 18.4c13.993-3.833 22.224-18.28 18.394-32.27l-56.962-208.2c-3.83-13.987-18.27-22.228-32.254-18.394C78.607 5.157 70.373 19.609 74.203 33.6z");
}

.t3kxshl8m {
  fill: var(--svg-color--00b4f2, #00b4f2);
  d: path("m18.065 122.054l203.387 67.293c13.765 4.552 28.615-2.92 33.167-16.696c4.562-13.774-2.911-28.63-16.681-33.189L34.556 72.175C20.786 67.62 5.942 75.091 1.387 88.867c-4.55 13.775 2.924 28.635 16.682 33.187z");
}

</style>
