<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4xw6ab6k.css';
import '../../css/w/waaecn3wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4xw6ab6k"/><path class="waaecn3wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smart-plug-48" /></template>
