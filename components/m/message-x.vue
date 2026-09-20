<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdvfg9b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdvfg9b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:message-x" /></template>
