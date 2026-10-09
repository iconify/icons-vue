<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfu98d8ng.css';
import '../../css/p/pdm5qacug.css';
import '../../css/a/a-9h4gbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tfu98d8ng"/><path class="pdm5qacug"/><path class="a-9h4gbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:palm-tree-48-bold" /></template>
