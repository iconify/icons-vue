<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb0k45bkf.css';
import '../../css/f/ftn7apb3z.css';
import '../../css/q/qtoznccub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bb0k45bkf"/><path class="ftn7apb3z"/><path class="qtoznccub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:micro-hydro-48-bold" /></template>
