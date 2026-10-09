<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4447fbqf.css';
import '../../css/c/c-a3h2bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w4447fbqf"/><path class="c-a3h2bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-alert-48-bold" /></template>
