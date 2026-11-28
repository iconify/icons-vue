<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpakxm-mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpakxm-mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pin-plus" /></template>
