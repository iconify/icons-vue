<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iff06dboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iff06dboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:neutralinojs" /></template>
