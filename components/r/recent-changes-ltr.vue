<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arx7bg38m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="arx7bg38m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:recent-changes-ltr" /></template>
