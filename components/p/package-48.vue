<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcruq_b4u.css';
import '../../css/l/l3mikie3t.css';
import '../../css/v/vnl18uiss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bcruq_b4u"/><path class="l3mikie3t"/><path class="vnl18uiss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:package-48" /></template>
