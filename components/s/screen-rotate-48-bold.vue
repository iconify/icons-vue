<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi8o1qbbo.css';
import '../../css/o/o7xo-pl1v.css';
import '../../css/z/z-qwk0bfp.css';
import '../../css/p/phykisuce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oi8o1qbbo"/><path class="o7xo-pl1v"/><path class="z-qwk0bfp"/><path class="phykisuce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screen-rotate-48-bold" /></template>
