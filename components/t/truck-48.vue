<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xujk5fdpi.css';
import '../../css/w/wg4scnbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xujk5fdpi"/><path class="wg4scnbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:truck-48" /></template>
