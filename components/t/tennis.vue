<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj6eepmbw.css';
import '../../css/m/m-0zmcczs.css';
import '../../css/x/x9ach8b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="dj6eepmbw"/><path class="m-0zmcczs"/><path class="x9ach8b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tennis" /></template>
