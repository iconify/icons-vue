<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr8g-9bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr8g-9bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:send-hor-light" /></template>
