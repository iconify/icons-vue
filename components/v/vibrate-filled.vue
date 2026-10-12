<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr52ofb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr52ofb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:vibrate-filled" /></template>
