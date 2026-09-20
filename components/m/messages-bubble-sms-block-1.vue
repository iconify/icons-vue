<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky01pldxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky01pldxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:messages-bubble-sms-block-1" /></template>
