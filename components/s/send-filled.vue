<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdnjzzbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdnjzzbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:send-filled" /></template>
