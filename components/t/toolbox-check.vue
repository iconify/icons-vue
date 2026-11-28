<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3rcknotz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3rcknotz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:toolbox-check" /></template>
