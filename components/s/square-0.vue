<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikcs-8xax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikcs-8xax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:square-0" /></template>
