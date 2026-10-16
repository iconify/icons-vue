<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-lwp7znm.css';
import '../../css/p/puykbrbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n-lwp7znm"/><path class="puykbrbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tide-low-48-bold" /></template>
