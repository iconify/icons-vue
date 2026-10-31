<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we6vmqb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we6vmqb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-high-round" /></template>
