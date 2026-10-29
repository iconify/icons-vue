<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_90oabvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_90oabvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:star-plus" /></template>
