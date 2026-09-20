<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs-u-bc-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs-u-bc-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sip-fill" /></template>
