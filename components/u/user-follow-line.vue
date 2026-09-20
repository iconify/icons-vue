<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u15gl81xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u15gl81xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-follow-line" /></template>
