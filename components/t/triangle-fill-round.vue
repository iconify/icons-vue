<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quwjrz4se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quwjrz4se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-fill-round" /></template>
