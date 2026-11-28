<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc3et9b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc3et9b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sofa" /></template>
