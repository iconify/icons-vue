<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9v855hut.css';
import '../../css/y/y7bdy3xji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c9v855hut"/><path class="y7bdy3xji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-charger-48" /></template>
