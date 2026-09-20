<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vug20nb6u.css';
import '../../css/t/tvz5c1gug.css';
import '../../css/t/tjfe3abxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vug20nb6u"/><path class="tvz5c1gug"/><path class="tjfe3abxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rhel-dark" /></template>
