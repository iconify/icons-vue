<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-ftrm2ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-ftrm2ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:shuffle" /></template>
