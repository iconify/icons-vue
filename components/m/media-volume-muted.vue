<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1ysnnbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b1ysnnbms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-volume-muted" /></template>
