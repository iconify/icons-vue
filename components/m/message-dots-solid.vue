<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv_3wyb7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv_3wyb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-dots-solid" /></template>
