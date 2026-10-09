<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj3zoshwv.css';
import '../../css/v/vlib7y67t.css';
import '../../css/d/duqi8c8_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jj3zoshwv"/><path class="vlib7y67t"/><path class="duqi8c8_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:zoom-in-20-bold" /></template>
