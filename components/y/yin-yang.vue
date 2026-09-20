<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sht_tnnlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sht_tnnlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:yin-yang" /></template>
