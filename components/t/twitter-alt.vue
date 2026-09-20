<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu3rknbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu3rknbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:twitter-alt" /></template>
