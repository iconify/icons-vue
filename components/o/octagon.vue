<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbl9e-bnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbl9e-bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:octagon" /></template>
