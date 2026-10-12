<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmexh2bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmexh2bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:send-filled" /></template>
