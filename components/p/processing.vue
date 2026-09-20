<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un5mhlcug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="un5mhlcug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:processing" /></template>
