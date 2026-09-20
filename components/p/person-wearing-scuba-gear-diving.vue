<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q28dagboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q28dagboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-scuba-gear-diving" /></template>
