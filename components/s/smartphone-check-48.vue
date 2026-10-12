<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z35ia5jrg.css';
import '../../css/p/p8lm6n71m.css';
import '../../css/z/z4sj3ixdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z35ia5jrg"/><path class="p8lm6n71m"/><path class="z4sj3ixdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-check-48" /></template>
