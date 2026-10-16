<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9v855hut.css';
import '../../css/n/ny_2c4bnf.css';
import '../../css/n/nwcxv7blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c9v855hut"/><path class="ny_2c4bnf"/><path class="nwcxv7blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:marker-hydrogen-48" /></template>
