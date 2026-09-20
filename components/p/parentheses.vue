<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-2te59_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-2te59_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:parentheses" /></template>
