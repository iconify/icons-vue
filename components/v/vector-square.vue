<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tztqyrvud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tztqyrvud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vector-square" /></template>
