<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhre5kbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhre5kbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:toggle-on" /></template>
