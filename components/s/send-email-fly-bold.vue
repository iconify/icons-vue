<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cio1c0bky.css';
import '../../css/a/ave95yb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cio1c0bky"/><path class="ave95yb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:send-email-fly-bold" /></template>
