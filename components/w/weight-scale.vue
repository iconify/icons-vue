<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jirkywbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jirkywbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:weight-scale" /></template>
