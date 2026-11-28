<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_v203bkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="z_v203bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:send-backward-light" /></template>
