<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g10l5m80q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g10l5m80q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-minus" /></template>
