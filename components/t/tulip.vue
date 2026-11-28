<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej982evue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej982evue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tulip" /></template>
