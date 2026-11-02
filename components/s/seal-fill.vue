<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go9y56blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go9y56blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:seal-fill" /></template>
