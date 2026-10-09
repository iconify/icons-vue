<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpmvct1xz.css';
import '../../css/e/exkkztbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kpmvct1xz"/><path class="exkkztbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-x-48" /></template>
