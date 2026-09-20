<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq_8decro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq_8decro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vsco" /></template>
