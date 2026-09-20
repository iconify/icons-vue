<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgvia1b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgvia1b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:male" /></template>
