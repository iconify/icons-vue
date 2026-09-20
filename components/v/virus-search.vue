<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdmpuvbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdmpuvbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:virus-search" /></template>
