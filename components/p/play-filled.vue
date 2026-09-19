<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9yyosbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9yyosbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:play-filled" /></template>
