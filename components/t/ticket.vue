<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezz8hjg-s.css';
import '../../css/u/uj_v03r8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ezz8hjg-s"/><path class="uj_v03r8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:ticket" /></template>
