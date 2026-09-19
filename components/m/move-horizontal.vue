<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekwir30sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekwir30sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:move-horizontal" /></template>
