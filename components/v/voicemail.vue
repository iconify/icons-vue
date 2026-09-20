<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpotbvbbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpotbvbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:voicemail" /></template>
