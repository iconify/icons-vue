<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5a8qrbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5a8qrbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:play-gloss" /></template>
