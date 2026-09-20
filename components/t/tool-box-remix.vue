<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0l-glbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0l-glbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tool-box-remix" /></template>
