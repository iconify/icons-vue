<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e88q4ab4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e88q4ab4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shield-lock-filled" /></template>
