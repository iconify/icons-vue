<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xct7y4b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xct7y4b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:star" /></template>
