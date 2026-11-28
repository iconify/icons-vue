<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxrmlobex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxrmlobex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sun-off" /></template>
