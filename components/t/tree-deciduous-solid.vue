<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8_ac1tmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8_ac1tmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tree-deciduous-solid" /></template>
