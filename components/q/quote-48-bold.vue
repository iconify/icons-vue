<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/una0qyech.css';
import '../../css/g/gzmmb_5vu.css';
import '../../css/x/x5dd3rcaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="una0qyech"/><path class="gzmmb_5vu"/><path class="x5dd3rcaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:quote-48-bold" /></template>
