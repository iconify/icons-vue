<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thp9z3b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thp9z3b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:push-notification-outline" /></template>
