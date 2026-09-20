<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e06ybtbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e06ybtbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:torii" /></template>
