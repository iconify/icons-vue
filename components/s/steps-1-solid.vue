<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gznph3b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gznph3b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:steps-1-solid" /></template>
