<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c699pgcco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c699pgcco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:numbered-list-left" /></template>
