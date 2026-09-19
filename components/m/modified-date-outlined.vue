<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rym86fbok.css';
import '../../css/n/ni4bbebcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rym86fbok"/><path class="ni4bbebcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:modified-date-outlined" /></template>
