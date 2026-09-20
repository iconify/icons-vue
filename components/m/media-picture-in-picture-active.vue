<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw6-ov3tm.css';
import '../../css/l/liz26ccin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lw6-ov3tm"/><path class="liz26ccin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-picture-in-picture-active" /></template>
