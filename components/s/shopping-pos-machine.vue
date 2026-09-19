<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcdw70s4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":24};
const content = `<path class="hcdw70s4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopping-pos-machine" /></template>
