<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nris9bbgu.css';
import '../../css/a/ak9f-hbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nris9bbgu"/><path class="ak9f-hbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:saw-48" /></template>
