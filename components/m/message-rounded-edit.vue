<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3qu9vwbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3qu9vwbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-rounded-edit" /></template>
