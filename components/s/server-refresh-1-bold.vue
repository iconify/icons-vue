<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyw7qtbor.css';
import '../../css/g/g-an08bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyw7qtbor"/><path class="g-an08bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:server-refresh-1-bold" /></template>
