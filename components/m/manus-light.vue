<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pglcr0mfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":60,"height":60};
const content = `<path clip-rule="evenodd" class="pglcr0mfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:manus-light" /></template>
