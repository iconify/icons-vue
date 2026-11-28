<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/untp8k7je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="untp8k7je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tabs" /></template>
