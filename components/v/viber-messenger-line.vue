<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxval3blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxval3blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:viber-messenger-line" /></template>
