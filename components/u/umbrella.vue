<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrm7n2blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="xrm7n2blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:umbrella" /></template>
