<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5d23vbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5d23vbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tqdm" /></template>
