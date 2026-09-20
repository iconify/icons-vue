<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voelf1xfy.css';
import '../../css/p/p7ctu3bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="voelf1xfy"/><path class="p7ctu3bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:power-off" /></template>
