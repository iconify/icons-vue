<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsbde-b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsbde-b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-pen-solid" /></template>
