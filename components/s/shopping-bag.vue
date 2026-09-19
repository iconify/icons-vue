<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dka9-7apg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dka9-7apg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shopping-bag" /></template>
