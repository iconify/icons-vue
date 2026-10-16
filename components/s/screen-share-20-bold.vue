<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_736ebfb.css';
import '../../css/w/w0poz4bns.css';
import '../../css/c/c2cej4bnh.css';
import '../../css/u/uksk150fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k_736ebfb"/><path class="w0poz4bns"/><path class="c2cej4bnh"/><path class="uksk150fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screen-share-20-bold" /></template>
