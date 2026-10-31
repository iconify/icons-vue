<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1mtn1e3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1mtn1e3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:store-fill-round" /></template>
