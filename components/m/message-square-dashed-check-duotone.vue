<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjoc47qyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjoc47qyp primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-dashed-check-duotone" /></template>
