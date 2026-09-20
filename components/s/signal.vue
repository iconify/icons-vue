<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndwl507qf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndwl507qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:signal" /></template>
