<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rppm-nbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rppm-nbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:monitor-pause" /></template>
