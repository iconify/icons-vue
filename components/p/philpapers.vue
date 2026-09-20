<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp2ktcbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yp2ktcbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:philpapers" /></template>
