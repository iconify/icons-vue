<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz71x_bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hz71x_bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:virtual-reality" /></template>
