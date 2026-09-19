<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0ojwh5bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0ojwh5bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-circle-captions-filled" /></template>
