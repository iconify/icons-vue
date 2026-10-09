<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5ciubb6p.css';
import '../../css/i/iowuvxnvk.css';
import '../../css/r/rw-4knbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e5ciubb6p"/><path class="iowuvxnvk"/><path class="rw-4knbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:meeting-48-bold" /></template>
