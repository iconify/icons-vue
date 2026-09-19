<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcxp6pb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcxp6pb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sun-dim" /></template>
