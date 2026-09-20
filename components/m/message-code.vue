<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rizr8xbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rizr8xbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-code" /></template>
