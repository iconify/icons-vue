<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-iypzbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-iypzbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:message-rounded-error" /></template>
