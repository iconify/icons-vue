<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5xbnj3bp.css';
import '../../css/t/t1563xbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5xbnj3bp"/><rect class="t1563xbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:poll-filled" /></template>
