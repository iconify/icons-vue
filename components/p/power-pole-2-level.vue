<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paa32pj0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="paa32pj0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-pole-2-level" /></template>
