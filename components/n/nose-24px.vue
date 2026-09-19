<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp37ko-fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp37ko-fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:nose-24px" /></template>
