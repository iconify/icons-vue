<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l01w4f3bq.css';
import '../../css/n/n6es8zk1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l01w4f3bq"/><path class="n6es8zk1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:settings-hammer" /></template>
