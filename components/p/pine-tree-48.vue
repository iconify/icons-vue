<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh5gb5v9g.css';
import '../../css/u/uo0uz19so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jh5gb5v9g"/><path class="uo0uz19so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pine-tree-48" /></template>
