<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osmsw0baw.css';
import '../../css/u/u7-rv5cxi.css';
import '../../css/u/ujxr68ihv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="osmsw0baw"/><path class="u7-rv5cxi"/><path class="ujxr68ihv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:sim-card" /></template>
