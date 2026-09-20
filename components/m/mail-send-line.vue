<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhmsmb9kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhmsmb9kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-send-line" /></template>
