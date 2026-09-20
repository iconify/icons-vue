<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ous84lbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="ous84lbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:shipping" /></template>
