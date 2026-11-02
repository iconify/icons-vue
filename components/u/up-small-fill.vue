<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2_0k7b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2_0k7b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:up-small-fill" /></template>
