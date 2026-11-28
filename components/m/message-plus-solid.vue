<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xipteqb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xipteqb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-plus-solid" /></template>
