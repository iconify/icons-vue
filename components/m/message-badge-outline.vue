<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyx1jft5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyx1jft5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-badge-outline" /></template>
