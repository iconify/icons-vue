<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijgh9kb6y.css';
import '../../css/r/r409soybt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ijgh9kb6y"/><path class="r409soybt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-48" /></template>
