<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er7xp67md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er7xp67md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:toolbox" /></template>
