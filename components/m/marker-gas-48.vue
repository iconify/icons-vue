<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9v855hut.css';
import '../../css/k/k-xlivbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c9v855hut"/><path class="k-xlivbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-gas-48" /></template>
