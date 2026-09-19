<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slxefw72b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slxefw72b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-detail-filled" /></template>
