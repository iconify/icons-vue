<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dck9ixbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dck9ixbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:tally-4" /></template>
