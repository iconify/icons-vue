<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2q_u0bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2q_u0bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sparkfun" /></template>
