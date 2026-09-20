<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz74pvtjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz74pvtjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-fill-24" /></template>
