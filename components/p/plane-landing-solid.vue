<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6tms1bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6tms1bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plane-landing-solid" /></template>
