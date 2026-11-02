<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw6p4ccxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw6p4ccxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-send-fill" /></template>
