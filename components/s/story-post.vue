<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkgk_7lou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkgk_7lou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:story-post" /></template>
