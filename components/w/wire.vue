<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhua0w9kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhua0w9kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wire" /></template>
