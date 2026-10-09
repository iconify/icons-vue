<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5vpx869x.css';
import '../../css/c/cjykg8bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r5vpx869x"/><path class="cjykg8bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:subsea-cable-48" /></template>
