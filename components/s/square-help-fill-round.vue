<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h368z8r3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h368z8r3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-help-fill-round" /></template>
