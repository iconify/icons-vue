<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg9_1g56y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg9_1g56y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:textalign-justifycenter" /></template>
