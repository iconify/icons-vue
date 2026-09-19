<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a598-bvni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a598-bvni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-bubble-detail-filled" /></template>
