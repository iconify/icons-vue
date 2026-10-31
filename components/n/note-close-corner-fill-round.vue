<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voweq_oeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voweq_oeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-close-corner-fill-round" /></template>
