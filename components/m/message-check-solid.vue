<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymv6giefm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymv6giefm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-check-solid" /></template>
