<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbdvb1a7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbdvb1a7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:workflow-outline" /></template>
