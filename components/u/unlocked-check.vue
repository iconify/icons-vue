<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr6r9tbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr6r9tbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:unlocked-check" /></template>
