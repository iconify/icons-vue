<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvschac7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvschac7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:zip-file" /></template>
