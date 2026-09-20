<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6gnq9bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6gnq9bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tv4-play" /></template>
