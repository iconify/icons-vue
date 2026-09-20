<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neg8u-b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="neg8u-b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trueconf-light" /></template>
