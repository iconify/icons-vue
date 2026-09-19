<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evpczub_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="evpczub_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:pencil" /></template>
