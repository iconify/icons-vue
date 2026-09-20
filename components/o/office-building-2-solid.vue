<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6c40bb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6c40bb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:office-building-2-solid" /></template>
