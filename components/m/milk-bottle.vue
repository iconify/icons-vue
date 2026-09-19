<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwa2rfbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwa2rfbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:milk-bottle" /></template>
