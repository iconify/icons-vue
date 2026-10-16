<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eumvrmloj.css';
import '../../css/o/on432c78a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eumvrmloj"/><path class="on432c78a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scrubber-48" /></template>
