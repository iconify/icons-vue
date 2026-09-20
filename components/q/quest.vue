<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1bdj-_1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1bdj-_1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:quest" /></template>
