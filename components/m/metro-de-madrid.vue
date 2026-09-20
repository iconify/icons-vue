<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4fi4u11f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4fi4u11f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:metro-de-madrid" /></template>
