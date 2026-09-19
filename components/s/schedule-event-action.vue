<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy2kve2lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gy2kve2lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:schedule-event-action" /></template>
