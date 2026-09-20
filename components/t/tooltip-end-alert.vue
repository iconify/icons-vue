<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7pgm6_vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="b7pgm6_vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-end-alert" /></template>
