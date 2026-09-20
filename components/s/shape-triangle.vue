<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py9te0bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py9te0bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:shape-triangle" /></template>
