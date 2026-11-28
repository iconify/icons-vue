<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3peuop-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3peuop-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:split-solid" /></template>
