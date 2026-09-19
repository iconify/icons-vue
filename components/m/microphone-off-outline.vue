<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiaxfabid.css';
import '../../css/d/dpr9gubjx.css';
import '../../css/x/x0-csbbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiaxfabid"/><path clip-rule="evenodd" class="dpr9gubjx"/><path class="x0-csbbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:microphone-off-outline" /></template>
