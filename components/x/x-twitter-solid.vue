<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/javx1rslg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="javx1rslg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:x-twitter-solid" /></template>
