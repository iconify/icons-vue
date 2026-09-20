<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6llgabii.css';
import '../../css/q/q3ki42tjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6llgabii"/><path class="q3ki42tjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:octagon-check" /></template>
