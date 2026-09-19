<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oneiljmfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oneiljmfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:mode-dark-thin" /></template>
