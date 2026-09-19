<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp2y35std.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp2y35std"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:microphone-alt-2-filled" /></template>
