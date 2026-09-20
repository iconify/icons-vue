<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmc9s-k4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmc9s-k4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-24" /></template>
