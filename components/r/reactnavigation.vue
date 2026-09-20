<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uorsw2bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uorsw2bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:reactnavigation" /></template>
