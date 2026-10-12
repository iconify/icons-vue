<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8v5izblz.css';
import '../../css/e/e_y__bbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z8v5izblz"/><path class="e_y__bbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plunger-48-bold" /></template>
