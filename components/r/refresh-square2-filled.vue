<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt63arb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt63arb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:refresh-square2-filled" /></template>
