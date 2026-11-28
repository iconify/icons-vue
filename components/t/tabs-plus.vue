<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_c1d8fvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_c1d8fvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tabs-plus" /></template>
