<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdrf_dzwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdrf_dzwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-dots-filled" /></template>
