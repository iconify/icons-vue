<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpu66u8hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpu66u8hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-plus-solid" /></template>
