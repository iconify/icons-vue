<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3csk8btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:quote-single-end-fill" /></template>
<style>
.k3csk8btg {
  fill: currentColor;
  d: path("M16.5 9.5C16.5 13.3132 14.5217 16.8533 11.2741 18.8517C11.1165 18.9487 10.935 19 10.75 19C10.1977 19 9.75 18.5523 9.75 18C9.75 17.7071 9.8784 17.429 10.1012 17.239C10.6275 16.7904 10.9306 16.1336 10.9306 15.4421C10.9306 14.5984 10.4806 13.8189 9.75 13.3971C8.3577 12.5933 7.5 11.1077 7.5 9.5C7.5 7.0147 9.5147 5 12 5C14.4853 5 16.5 7.0147 16.5 9.5Z");
}

</style>
