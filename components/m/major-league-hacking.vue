<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yekkhzb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yekkhzb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:major-league-hacking" /></template>
