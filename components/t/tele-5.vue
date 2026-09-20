<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc3y73bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc3y73bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tele-5" /></template>
