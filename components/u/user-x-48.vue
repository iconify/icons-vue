<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdkgyrbga.css';
import '../../css/s/sd_vembah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gdkgyrbga"/><path class="sd_vembah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-x-48" /></template>
