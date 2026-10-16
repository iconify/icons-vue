<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_ml6hb0a.css';
import '../../css/g/g66uptbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i_ml6hb0a"/><path class="g66uptbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:variable-resistor-48" /></template>
