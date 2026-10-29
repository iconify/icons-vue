<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swao-2bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swao-2bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-heart-solid" /></template>
