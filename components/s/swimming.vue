<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3ffpbbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3ffpbbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:swimming" /></template>
