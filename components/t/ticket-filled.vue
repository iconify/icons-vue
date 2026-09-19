<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wap7h8uas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wap7h8uas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:ticket-filled" /></template>
