<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lam3n-0ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lam3n-0ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:night" /></template>
