<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd7db9bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd7db9bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:microwave" /></template>
