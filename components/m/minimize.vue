<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhug2jvjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhug2jvjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:minimize" /></template>
