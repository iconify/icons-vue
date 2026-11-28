<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqlb4602y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqlb4602y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:prompt-x" /></template>
