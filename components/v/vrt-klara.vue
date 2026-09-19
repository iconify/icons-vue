<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd_dp2bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd_dp2bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:vrt-klara" /></template>
