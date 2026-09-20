<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2xt3z6tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="r2xt3z6tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:sigma" /></template>
