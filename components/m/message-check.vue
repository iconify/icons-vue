<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xenaye8jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xenaye8jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-check" /></template>
