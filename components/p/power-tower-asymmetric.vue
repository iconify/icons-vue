<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vppgqcbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vppgqcbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-asymmetric" /></template>
