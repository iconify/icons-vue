<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvw_whb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvw_whb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:play-store" /></template>
