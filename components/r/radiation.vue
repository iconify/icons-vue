<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmaui0_pa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmaui0_pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:radiation" /></template>
