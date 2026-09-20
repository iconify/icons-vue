<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzd5e6bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hzd5e6bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:notification-alarm-2-remix" /></template>
