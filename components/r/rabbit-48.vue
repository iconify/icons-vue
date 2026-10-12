<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhg_0dbbc.css';
import '../../css/p/pjqal2h2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bhg_0dbbc"/><path class="pjqal2h2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rabbit-48" /></template>
