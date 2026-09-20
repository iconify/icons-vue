<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaa1wubfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaa1wubfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:whatsapp" /></template>
