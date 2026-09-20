<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy9xttbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy9xttbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:metacritic" /></template>
