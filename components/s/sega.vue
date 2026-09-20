<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqnd2uppl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqnd2uppl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sega" /></template>
