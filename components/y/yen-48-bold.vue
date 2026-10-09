<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp8l54blm.css';
import '../../css/u/udr_1ybfu.css';
import '../../css/y/ymqwf0tfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bp8l54blm"/><path class="udr_1ybfu"/><path class="ymqwf0tfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:yen-48-bold" /></template>
