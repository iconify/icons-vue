<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moxj19q1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moxj19q1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square" /></template>
