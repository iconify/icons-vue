<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly6i-fbqm.css';
import '../../css/n/ndjzvdb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ly6i-fbqm"/><path class="ndjzvdb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:snowboard-48" /></template>
