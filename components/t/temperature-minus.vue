<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqoqmd7_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqoqmd7_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:temperature-minus" /></template>
