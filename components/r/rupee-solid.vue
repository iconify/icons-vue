<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gav4x1b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gav4x1b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rupee-solid" /></template>
