<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj41r93vd.css';
import '../../css/n/nfvrmwb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jj41r93vd"/><path class="nfvrmwb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:saw-20-bold" /></template>
