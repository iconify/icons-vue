<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_u8q-bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_u8q-bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:settings-6-fill" /></template>
