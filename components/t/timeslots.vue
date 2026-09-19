<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_1_ebbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2080,"height":1504};
const content = `<path class="n_1_ebbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:timeslots" /></template>
