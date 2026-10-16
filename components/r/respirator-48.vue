<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1w3r8bvp.css';
import '../../css/j/je2jee5cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z1w3r8bvp"/><path class="je2jee5cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:respirator-48" /></template>
