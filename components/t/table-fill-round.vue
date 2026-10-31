<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfqqx6mhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfqqx6mhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-fill-round" /></template>
