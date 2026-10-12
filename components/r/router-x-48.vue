<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv5a9blrh.css';
import '../../css/n/n-i0a3b8w.css';
import '../../css/b/bdkl8-dne.css';
import '../../css/j/j3cy-fbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rv5a9blrh"/><path class="n-i0a3b8w"/><path class="bdkl8-dne"/><path class="j3cy-fbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:router-x-48" /></template>
