<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5dwkmnlz.css';
import '../../css/w/w50wxabok.css';
import '../../css/g/gdzqqzccu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1104,"height":1104};
const content = `<path class="f5dwkmnlz"/><path class="w50wxabok"/><path class="gdzqqzccu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:visernic" /></template>
