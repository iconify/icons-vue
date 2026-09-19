<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwixg__8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwixg__8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:more-grid-small" /></template>
