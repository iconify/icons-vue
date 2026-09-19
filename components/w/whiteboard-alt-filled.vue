<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q34h2vb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q34h2vb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:whiteboard-alt-filled" /></template>
