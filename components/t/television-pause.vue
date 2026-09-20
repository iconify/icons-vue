<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em8bb6bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em8bb6bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:television-pause" /></template>
