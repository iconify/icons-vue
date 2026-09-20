<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3c1a2btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3c1a2btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:squarespace" /></template>
