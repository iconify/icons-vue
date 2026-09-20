<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uff2ydbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uff2ydbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-tv-logo-block" /></template>
