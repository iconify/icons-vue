<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4721q_ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path paint-order="fill markers stroke" class="o4721q_ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:quokka" /></template>
