<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5tu98qwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="h5tu98qwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:map" /></template>
