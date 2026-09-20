<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul6au0wgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul6au0wgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-function" /></template>
