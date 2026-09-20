<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-4dk0bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-4dk0bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:triangle" /></template>
