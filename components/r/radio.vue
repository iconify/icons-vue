<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcagx4xdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hcagx4xdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:radio" /></template>
