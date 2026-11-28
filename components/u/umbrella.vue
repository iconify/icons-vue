<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv94c6bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv94c6bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:umbrella" /></template>
