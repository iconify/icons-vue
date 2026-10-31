<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4q4gacap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4q4gacap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:users-fill-round" /></template>
