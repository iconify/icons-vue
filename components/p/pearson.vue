<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iecc9yb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iecc9yb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pearson" /></template>
