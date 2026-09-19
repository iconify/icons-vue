<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grm9hxbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grm9hxbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:move" /></template>
