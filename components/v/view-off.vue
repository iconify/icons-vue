<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwtoeebil.css';
import '../../css/j/jg4fprb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vwtoeebil"/><path class="jg4fprb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:view-off" /></template>
