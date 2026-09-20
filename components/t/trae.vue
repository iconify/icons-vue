<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em3krwbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em3krwbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:trae" /></template>
