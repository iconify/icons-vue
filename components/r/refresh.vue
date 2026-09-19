<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr1l_cgam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="fr1l_cgam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:refresh" /></template>
