<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un1upsagj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un1upsagj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:trash" /></template>
