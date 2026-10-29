<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzh__gl_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzh__gl_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-plus-solid" /></template>
