<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2-wedcdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2-wedcdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mubi" /></template>
