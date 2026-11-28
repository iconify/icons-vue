<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvxll9bne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvxll9bne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:store-x" /></template>
