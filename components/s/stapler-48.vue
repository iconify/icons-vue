<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeh2-4bai.css';
import '../../css/s/s8q5ribee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xeh2-4bai"/><path class="s8q5ribee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stapler-48" /></template>
