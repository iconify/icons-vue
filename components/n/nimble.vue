<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5y0id6qu.css';
import '../../css/p/pyhgc0wha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a5y0id6qu"/><path class="pyhgc0wha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nimble" /></template>
