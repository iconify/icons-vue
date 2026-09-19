<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_9z6yunr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_9z6yunr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:package" /></template>
