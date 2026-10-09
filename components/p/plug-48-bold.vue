<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6rccpbxu.css';
import '../../css/j/jh8uq2e7m.css';
import '../../css/n/nl2f48bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z6rccpbxu"/><path class="jh8uq2e7m"/><path class="nl2f48bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plug-48-bold" /></template>
