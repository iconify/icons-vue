<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9uiqibbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9uiqibbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:readme" /></template>
