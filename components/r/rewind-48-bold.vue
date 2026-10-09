<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3pwufbep.css';
import '../../css/i/ifs4a46sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v3pwufbep"/><path class="ifs4a46sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rewind-48-bold" /></template>
