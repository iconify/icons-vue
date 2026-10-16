<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpv7mcc4r.css';
import '../../css/m/m2v5ujr4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hpv7mcc4r"/><path class="m2v5ujr4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-cross-48" /></template>
