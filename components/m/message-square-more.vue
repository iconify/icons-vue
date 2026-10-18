<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saot2obzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saot2obzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:message-square-more" /></template>
