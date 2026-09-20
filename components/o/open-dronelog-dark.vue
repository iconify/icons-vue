<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygxly9bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygxly9bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:open-dronelog-dark" /></template>
