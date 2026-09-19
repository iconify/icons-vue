<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onr2f2ppx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onr2f2ppx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:translate" /></template>
