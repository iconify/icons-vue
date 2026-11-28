<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcz2pcbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcz2pcbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-info" /></template>
