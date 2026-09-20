<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhjhq80ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhjhq80ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:prefect" /></template>
