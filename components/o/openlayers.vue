<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":259};
const content = `<path class="v8ywwtcts"/><path class="xuudkib8s"/><path class="kque0hplw"/><path class="afaj2b4bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:openlayers" /></template>
<style>
.afaj2b4bk {
  fill: var(--svg-color--fff, #fff);
  d: path("M244.31 81.1a43 43 0 0 0-2.3-2.077L161.99 12.33c-18.688-15.577-49.267-15.574-67.952 0L14.011 79.023c-18.681 15.58-18.681 41.058.003 56.634l8.612 7.176C45.142 115.79 121.074 40.853 244.31 81.1");
  opacity: var(--svg-opacity--0-15, 0.15);
}

.kque0hplw {
  fill: var(--svg-color--35bbce, #35bbce);
  d: path("M161.974 12.319L241.99 78.95c18.68 15.562 18.683 41.017-.003 56.578l-80.013 66.63c-18.69 15.565-49.266 15.56-67.945 0l-80.016-66.63C-4.67 119.97-4.67 94.513 14.01 78.951l80.019-66.632c18.682-15.56 49.26-15.563 67.945 0");
}

.v8ywwtcts {
  fill: var(--svg-color--015965, #015965);
  d: path("M94.029 57.213c18.682-15.559 49.26-15.562 67.945 0l80.016 66.632c18.68 15.561 18.683 41.015-.003 56.577l-80.013 66.63c-18.69 15.564-49.266 15.56-67.945 0l-80.016-66.63c-18.683-15.56-18.683-41.016-.003-56.577z");
}

.xuudkib8s {
  fill: var(--svg-color--e5e5e5, #e5e5e5);
  d: path("M94.029 35.561c18.682-15.559 49.26-15.562 67.945 0l80.016 66.633c18.68 15.562 18.683 41.017-.003 56.578l-80.013 66.63c-18.69 15.564-49.266 15.56-67.945 0l-80.016-66.63c-18.683-15.56-18.683-41.016-.003-56.578z");
}

</style>
