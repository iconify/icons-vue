<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/son5b-qcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="son5b-qcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:vector-distort-solid" /></template>
