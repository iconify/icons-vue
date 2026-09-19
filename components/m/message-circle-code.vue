<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmtq3ybvx.css';
import '../../css/f/fu72iwgtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmtq3ybvx"/><path class="fu72iwgtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-code" /></template>
