<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjr-_su-k.css';
import '../../css/l/l_cw2_bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xjr-_su-k"/><path class="l_cw2_bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:message-queue" /></template>
