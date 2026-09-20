<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c55fx2b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c55fx2b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:podcast-addict" /></template>
