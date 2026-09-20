<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfjf88b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfjf88b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:outbox" /></template>
