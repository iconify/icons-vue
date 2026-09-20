<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hufrxye1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hufrxye1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:reactive-resume" /></template>
