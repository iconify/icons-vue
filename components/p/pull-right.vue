<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_l0zgbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="v_l0zgbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:pull-right" /></template>
