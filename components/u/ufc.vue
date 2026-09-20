<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unl-a7bqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unl-a7bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ufc" /></template>
