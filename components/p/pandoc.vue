<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unxxiy_1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unxxiy_1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pandoc" /></template>
