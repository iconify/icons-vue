<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-qjnfbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-qjnfbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-image-filled" /></template>
