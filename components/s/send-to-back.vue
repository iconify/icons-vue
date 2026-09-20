<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym5ag0pcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym5ag0pcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:send-to-back" /></template>
