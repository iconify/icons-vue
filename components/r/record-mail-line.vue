<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p42mq7fqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p42mq7fqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:record-mail-line" /></template>
