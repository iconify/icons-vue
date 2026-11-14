<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7mi3pbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7mi3pbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-multiple-01" /></template>
