<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0aox4ish.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0aox4ish"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:thin-big-down" /></template>
