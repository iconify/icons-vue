<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5qwrxb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5qwrxb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:stroke-drawing" /></template>
