<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em4j74_bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em4j74_bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:mermaid" /></template>
