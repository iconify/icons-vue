<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kionsguxs.css';
import '../../css/e/e1v-2sbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kionsguxs"/><path class="e1v-2sbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vuex-store" /></template>
