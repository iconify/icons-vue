<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj9y_zb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uj9y_zb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nginx-proxy-manager-light" /></template>
