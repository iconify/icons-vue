<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rroxyv3ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rroxyv3ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:snowpack" /></template>
