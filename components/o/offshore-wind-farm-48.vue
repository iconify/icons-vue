<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s68i8th-k.css';
import '../../css/r/r8211o0be.css';
import '../../css/j/j_9eze8nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s68i8th-k"/><path class="r8211o0be"/><path class="j_9eze8nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offshore-wind-farm-48" /></template>
