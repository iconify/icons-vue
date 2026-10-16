<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s85zepkkg.css';
import '../../css/r/r06c8lbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s85zepkkg"/><path class="r06c8lbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refuse-truck-48" /></template>
