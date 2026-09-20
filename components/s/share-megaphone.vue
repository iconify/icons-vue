<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duf3r5bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="duf3r5bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:share-megaphone" /></template>
