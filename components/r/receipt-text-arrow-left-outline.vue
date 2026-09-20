<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho3_thbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho3_thbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-arrow-left-outline" /></template>
