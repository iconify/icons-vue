<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2komvbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary w2komvbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:qr-code-duotone" /></template>
