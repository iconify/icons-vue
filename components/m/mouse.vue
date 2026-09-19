<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wax2jmrhx.css';
import '../../css/a/a44ck8zrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wax2jmrhx"/><path class="a44ck8zrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mouse" /></template>
