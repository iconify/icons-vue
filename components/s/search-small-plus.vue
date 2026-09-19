<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itdv8l7hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itdv8l7hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:search-small-plus" /></template>
