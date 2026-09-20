<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xae4rbczk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xae4rbczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:text-snippet" /></template>
