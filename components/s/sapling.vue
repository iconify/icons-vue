<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr1-omp7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr1-omp7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:sapling" /></template>
