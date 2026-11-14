<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddvgu8bvv.css';
import '../../css/a/a6tutdvgx.css';
import '../../css/s/shu3xdl9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="a6tutdvgx"/><circle class="shu3xdl9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:token-circle" /></template>
