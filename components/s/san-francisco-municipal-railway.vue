<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn3owobom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn3owobom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:san-francisco-municipal-railway" /></template>
