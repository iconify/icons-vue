<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsr384viw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsr384viw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-x-filled" /></template>
