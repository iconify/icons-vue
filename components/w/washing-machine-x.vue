<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3um52bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3um52bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:washing-machine-x" /></template>
