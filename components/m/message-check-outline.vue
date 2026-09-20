<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa0umvb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa0umvb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-check-outline" /></template>
