<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g15t1bclt.css';
import '../../css/j/j0qwephmf.css';
import '../../css/q/qq-n_ibfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g15t1bclt"/><path class="j0qwephmf"/><path class="qq-n_ibfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-treatment-48-bold" /></template>
