<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrb8-hcea.css';
import '../../css/i/i46axmbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrb8-hcea"/><path class="i46axmbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:send-email-envelope-bold" /></template>
