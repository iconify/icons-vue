<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7rlznb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v7rlznb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:wave-sine-16" /></template>
