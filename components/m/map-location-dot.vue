<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxk7nn9kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="gxk7nn9kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:map-location-dot" /></template>
