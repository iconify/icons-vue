<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq61xm8en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq61xm8en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:phone-arrow-right" /></template>
