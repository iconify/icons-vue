<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd7i3ibcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gd7i3ibcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:window-close" /></template>
