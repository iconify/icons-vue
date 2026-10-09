<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igxsdr2uj.css';
import '../../css/o/oajmqbcrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="igxsdr2uj"/><path class="oajmqbcrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-search-48-bold" /></template>
