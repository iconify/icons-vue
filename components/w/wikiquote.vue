<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dotp4jdox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dotp4jdox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wikiquote" /></template>
