<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcsbmibcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcsbmibcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-double-small-fill-round" /></template>
