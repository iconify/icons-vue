<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbivy8bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":790,"left":200,"top":206};
const content = `<path class="sbivy8bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:react-aria" /></template>
