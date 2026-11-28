<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-sdhjb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-sdhjb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wave-square-solid" /></template>
