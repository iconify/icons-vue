<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gogk23mvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gogk23mvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:utility-valve-with-gas-flame" /></template>
