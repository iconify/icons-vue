<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5-lt0yws.css';
import '../../css/p/p6ha02euk.css';
import '../../css/r/ro0uxekvs.css';
import '../../css/y/ybbr6lous.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j5-lt0yws"/><path class="p6ha02euk"/><path class="ro0uxekvs"/><path class="ybbr6lous"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:soil-20-bold" /></template>
