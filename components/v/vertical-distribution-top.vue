<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf39gg-ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf39gg-ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:vertical-distribution-top" /></template>
