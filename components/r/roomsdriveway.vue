<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts_9zc_xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts_9zc_xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roomsdriveway" /></template>
