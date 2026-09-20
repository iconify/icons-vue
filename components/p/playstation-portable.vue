<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3klc7bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3klc7bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:playstation-portable" /></template>
