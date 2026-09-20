<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c19orcb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c19orcb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tree" /></template>
