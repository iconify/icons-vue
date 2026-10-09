<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-mslvbxr.css';
import '../../css/s/sbemsbi8m.css';
import '../../css/k/kb7wbni7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y-mslvbxr"/><path class="sbemsbi8m"/><path class="kb7wbni7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-line-20" /></template>
