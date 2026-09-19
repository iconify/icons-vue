<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdj57bb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="jdj57bb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:power" /></template>
