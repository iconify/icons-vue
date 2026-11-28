<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1l84_une.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1l84_une"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:molecule-plus" /></template>
