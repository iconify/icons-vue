<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psb2m6b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psb2m6b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:speaker-1-remix" /></template>
