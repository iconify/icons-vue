<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8vrn9u6r.css';
import '../../css/m/m3htm8bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r8vrn9u6r"/><path class="m3htm8bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:university-48" /></template>
