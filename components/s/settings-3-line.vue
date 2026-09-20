<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvec1l3uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvec1l3uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:settings-3-line" /></template>
