<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbxswfbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbxswfbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:math-divide" /></template>
