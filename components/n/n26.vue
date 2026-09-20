<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwb0a3hgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwb0a3hgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:n26" /></template>
