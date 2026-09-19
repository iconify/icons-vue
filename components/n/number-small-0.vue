<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_ebm6b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v_ebm6b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-small-0" /></template>
