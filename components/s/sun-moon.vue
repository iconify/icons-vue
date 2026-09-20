<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8nppju6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8nppju6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sun-moon" /></template>
