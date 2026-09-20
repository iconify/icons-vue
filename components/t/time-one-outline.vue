<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv74m9bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pv74m9bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:time-one-outline" /></template>
