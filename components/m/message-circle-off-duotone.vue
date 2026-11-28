<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3ld7sxot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y3ld7sxot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-circle-off-duotone" /></template>
