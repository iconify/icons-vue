<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnxcg4bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnxcg4bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:swiggy" /></template>
