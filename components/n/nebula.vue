<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu6kj3bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu6kj3bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nebula" /></template>
