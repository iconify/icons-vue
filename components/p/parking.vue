<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t313n7boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t313n7boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:parking" /></template>
