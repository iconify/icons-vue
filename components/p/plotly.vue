<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot9egiipf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ot9egiipf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:plotly" /></template>
