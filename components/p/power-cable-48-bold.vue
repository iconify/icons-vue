<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfbb1fbyd.css';
import '../../css/h/h4_86xb7u.css';
import '../../css/o/o8n6aqd3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kfbb1fbyd"/><path class="h4_86xb7u"/><path class="o8n6aqd3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-cable-48-bold" /></template>
