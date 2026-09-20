<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3k-9lb1z.css';
import '../../css/u/u79pk-b6p.css';
import '../../css/e/exgpfybkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3k-9lb1z"/><path class="u79pk-b6p"/><path class="exgpfybkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:video-file-download-bold" /></template>
