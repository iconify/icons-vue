<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7lwjkbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7lwjkbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-check-filled" /></template>
