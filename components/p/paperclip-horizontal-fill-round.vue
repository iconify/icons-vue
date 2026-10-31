<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idr8lu39n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idr8lu39n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paperclip-horizontal-fill-round" /></template>
