<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx7nithiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx7nithiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:multiple-actions-chat" /></template>
