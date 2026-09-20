<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz592bkou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz592bkou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wwe" /></template>
