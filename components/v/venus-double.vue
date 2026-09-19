<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuz3m1xdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuz3m1xdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:venus-double" /></template>
