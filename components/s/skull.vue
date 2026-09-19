<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvz33rbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xvz33rbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:skull" /></template>
