<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f46bn0s6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f46bn0s6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-clock" /></template>
