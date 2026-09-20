<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5cz9jypa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5cz9jypa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:speech" /></template>
