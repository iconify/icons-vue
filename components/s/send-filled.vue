<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcoda5bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcoda5bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:send-filled" /></template>
