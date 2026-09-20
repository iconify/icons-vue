<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exr2ebttr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exr2ebttr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:vapor" /></template>
