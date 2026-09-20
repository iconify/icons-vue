<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_kb5ab6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_kb5ab6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:notist" /></template>
