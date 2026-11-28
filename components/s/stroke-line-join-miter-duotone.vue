<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdm67zyal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wdm67zyal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stroke-line-join-miter-duotone" /></template>
