<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgou47bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgou47bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:spinner" /></template>
