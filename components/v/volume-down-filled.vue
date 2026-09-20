<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw_9acb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw_9acb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:volume-down-filled" /></template>
