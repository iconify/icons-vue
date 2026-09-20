<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r02e4qbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r02e4qbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slider-v" /></template>
