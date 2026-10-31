<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf2qb-bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf2qb-bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-duocolor-round" /></template>
