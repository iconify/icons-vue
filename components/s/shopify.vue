<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmmc7xi2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="gmmc7xi2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:shopify" /></template>
