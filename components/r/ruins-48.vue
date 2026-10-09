<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c65-ehvfy.css';
import '../../css/d/d7tt0bbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c65-ehvfy"/><path class="d7tt0bbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ruins-48" /></template>
