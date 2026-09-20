<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m643enbfo.css';
import '../../css/x/xd0tx35ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m643enbfo"/><path class="xd0tx35ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:messages-bubble-square-graph" /></template>
