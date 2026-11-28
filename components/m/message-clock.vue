<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf_bgq3ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf_bgq3ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message-clock" /></template>
