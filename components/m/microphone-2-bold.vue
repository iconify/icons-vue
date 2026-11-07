<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzdt-h-hq.css';
import '../../css/w/w8iuawbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzdt-h-hq"/><path clip-rule="evenodd" class="w8iuawbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-2-bold" /></template>
