<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxs5gckpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxs5gckpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-question-mark-filled" /></template>
