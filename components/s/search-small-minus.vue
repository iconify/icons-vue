<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g22krckib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g22krckib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:search-small-minus" /></template>
