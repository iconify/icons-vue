<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6qtw7bof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6qtw7bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:navigation-check" /></template>
