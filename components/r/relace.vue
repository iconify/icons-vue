<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2i-107zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2i-107zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:relace" /></template>
