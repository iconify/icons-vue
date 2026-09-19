<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duhmbabhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duhmbabhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shopping-code-error" /></template>
