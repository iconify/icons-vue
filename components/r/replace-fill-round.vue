<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isnpccc1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isnpccc1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:replace-fill-round" /></template>
