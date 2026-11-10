<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4_eootwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4_eootwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:sigma-capital" /></template>
