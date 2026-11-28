<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-x5v2bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-x5v2bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:protractor" /></template>
