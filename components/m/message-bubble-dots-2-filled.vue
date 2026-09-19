<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc5a1e5us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc5a1e5us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-dots-2-filled" /></template>
