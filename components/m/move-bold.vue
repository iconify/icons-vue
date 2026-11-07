<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnoj3cihf.css';
import '../../css/t/t4ld3deyo.css';
import '../../css/f/f8n3u4syj.css';
import '../../css/l/lgqb26d1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnoj3cihf"/><path class="t4ld3deyo"/><path class="f8n3u4syj"/><path class="lgqb26d1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-bold" /></template>
