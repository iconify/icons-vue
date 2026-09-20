<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmm4b2b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmm4b2b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:sunglasses-filled" /></template>
