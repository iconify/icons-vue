<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9wnyfbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9wnyfbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-seven-box-multiple-outline" /></template>
