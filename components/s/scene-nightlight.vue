<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gee_04tds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gee_04tds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:scene-nightlight" /></template>
