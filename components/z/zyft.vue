<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-fsm3b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":160,"height":62};
const content = `<path class="m-fsm3b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zyft" /></template>
