<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/r7zmk6dmj.css';
import '../../css/a/ae8_d9ber.css';
import '../../css/c/c4sbe-bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7zmk6dmj"/><path class="ae8_d9ber"/><path class="c4sbe-bgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:transaction" /></template>
