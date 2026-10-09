<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1iqz1-zd.css';
import '../../css/r/r0d7qbcdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h1iqz1-zd"/><path class="r0d7qbcdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sun-bolt-48-bold" /></template>
