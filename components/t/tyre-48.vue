<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zen2agbyu.css';
import '../../css/r/r_a_juvfe.css';
import '../../css/i/i5yaabj1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zen2agbyu"/><path class="r_a_juvfe"/><path class="i5yaabj1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tyre-48" /></template>
