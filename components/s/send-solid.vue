<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5957gb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5957gb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:send-solid" /></template>
