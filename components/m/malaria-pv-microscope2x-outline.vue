<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5dz2tbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z5dz2tbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:malaria-pv-microscope2x-outline" /></template>
