<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w98n7s1pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w98n7s1pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:send-plane-fill" /></template>
