<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk44c3j1d.css';
import '../../css/s/sf98jwb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk44c3j1d"/><path class="sf98jwb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:server-api-cloud" /></template>
