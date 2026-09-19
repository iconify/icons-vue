<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfocdbcrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gfocdbcrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:meteor" /></template>
