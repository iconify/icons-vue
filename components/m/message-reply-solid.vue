<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xytuqx64a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xytuqx64a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:message-reply-solid" /></template>
