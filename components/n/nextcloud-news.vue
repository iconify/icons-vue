<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp1v2sdoj.css';
import '../../css/w/wufxdip_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qp1v2sdoj"/><path class="wufxdip_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-news" /></template>
