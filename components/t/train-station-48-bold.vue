<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2ev-6zgp.css';
import '../../css/c/cpgk2abrw.css';
import '../../css/i/ikk4chbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b2ev-6zgp"/><path class="cpgk2abrw"/><path class="ikk4chbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:train-station-48-bold" /></template>
