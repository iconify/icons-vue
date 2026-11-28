<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpt1_qb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpt1_qb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:password-check" /></template>
