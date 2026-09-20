<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh87_f6pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh87_f6pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-follow-fill" /></template>
