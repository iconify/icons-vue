<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq_-9tbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq_-9tbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:transfer-text-filled" /></template>
