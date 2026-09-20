<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adtzc6b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adtzc6b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sympy" /></template>
