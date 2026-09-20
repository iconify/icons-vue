<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lky_zhbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lky_zhbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:string" /></template>
