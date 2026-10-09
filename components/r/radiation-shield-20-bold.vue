<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdw3vx8xp.css';
import '../../css/e/e1hzf-y8n.css';
import '../../css/f/fdsiutbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fdw3vx8xp"/><path class="e1hzf-y8n"/><path class="fdsiutbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:radiation-shield-20-bold" /></template>
