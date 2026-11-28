<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gguu4r_oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gguu4r_oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-4" /></template>
