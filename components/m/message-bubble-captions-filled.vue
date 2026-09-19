<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5-xnrwut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5-xnrwut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-captions-filled" /></template>
