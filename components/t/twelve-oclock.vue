<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="saaj2ubvm"/><path class="tmqb3n9-b"/><path class="xn9uw1yhs"/><path class="h5op3fw2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:twelve-oclock" /></template>
<style>
.h5op3fw2t {
  fill: var(--svg-color--788288, #788288);
  d: path("M33.751 31.989c0 1.434-.842 2.595-1.881 2.595s-1.885-1.163-1.885-2.595l-.004-15.194c0-1.43.846-2.593 1.881-2.591c1.039-.002 1.885 1.162 1.885 2.589z");
}

.saaj2ubvm {
  fill: var(--svg-color--e0e7ec, #e0e7ec);
  d: path("M61.38 31.868c0 16.303-13.216 29.519-29.519 29.519c-16.304 0-29.521-13.216-29.521-29.519c0-16.306 13.216-29.522 29.521-29.522c16.303 0 29.519 13.216 29.519 29.522");
}

.tmqb3n9-b {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M31.868 0C14.297 0 0 14.298 0 31.868c0 17.571 14.297 31.868 31.868 31.868s31.866-14.297 31.866-31.868S49.439 0 31.868 0m0 57.53c-14.15 0-25.664-11.515-25.664-25.664S17.717 6.202 31.868 6.202c14.15 0 25.661 11.513 25.661 25.664c0 14.15-11.511 25.664-25.661 25.664");
}

.xn9uw1yhs {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M29.997 10.994c0-1.432.844-2.593 1.883-2.593c1.037 0 1.884 1.162 1.884 2.593V31.99c0 1.434-.847 2.595-1.884 2.595c-1.039 0-1.883-1.161-1.883-2.595z");
}

</style>
