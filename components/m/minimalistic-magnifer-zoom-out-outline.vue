<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7kg5lbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7kg5lbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifer-zoom-out-outline" /></template>
