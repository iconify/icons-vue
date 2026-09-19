<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgg0ddbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgg0ddbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:movies-anywhere-text" /></template>
