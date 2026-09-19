<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzum8wbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yzum8wbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shield-impact" /></template>
