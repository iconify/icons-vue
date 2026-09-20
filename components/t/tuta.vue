<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-b7uhibq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-b7uhibq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tuta" /></template>
