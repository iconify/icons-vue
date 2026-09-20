<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwlb_qanr.css';
import '../../css/z/zt-7pdbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="jwlb_qanr"/><path class="zt-7pdbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:photos" /></template>
