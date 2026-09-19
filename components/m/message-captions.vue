<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p56h_bbeb.css';
import '../../css/y/yyi__d53g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p56h_bbeb"/><path class="yyi__d53g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-captions" /></template>
