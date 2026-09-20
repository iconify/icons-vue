<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5-gmmbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5-gmmbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:purism" /></template>
