<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mavdskbnx.css';
import '../../css/d/dke65eb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mavdskbnx"/><path class="dke65eb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:torch" /></template>
