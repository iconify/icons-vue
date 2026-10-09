<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmpmiyb4b.css';
import '../../css/v/v81ej1b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lmpmiyb4b"/><path class="v81ej1b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-medium-48-bold" /></template>
