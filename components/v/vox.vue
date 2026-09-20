<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqz78abfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqz78abfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vox" /></template>
