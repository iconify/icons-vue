<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bghxr8bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bghxr8bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:test-tube" /></template>
