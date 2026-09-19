<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm4hri4ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm4hri4ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:notes" /></template>
