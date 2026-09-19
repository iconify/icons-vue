<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_je-3caz.css';
import '../../css/j/jmyvgu6pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x_je-3caz"/><path class="jmyvgu6pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:streamlit" /></template>
