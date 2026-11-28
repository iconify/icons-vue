<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cio6d1bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cio6d1bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:motorcycle-solid" /></template>
