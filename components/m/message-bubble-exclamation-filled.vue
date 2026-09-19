<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gaki46b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gaki46b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-exclamation-filled" /></template>
