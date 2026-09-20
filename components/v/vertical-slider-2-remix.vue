<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf282rbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jf282rbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:vertical-slider-2-remix" /></template>
