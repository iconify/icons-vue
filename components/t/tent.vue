<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs3gbobre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs3gbobre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tent" /></template>
