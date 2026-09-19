<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgs3vg2ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vgs3vg2ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:objects-align-justify-vertical" /></template>
