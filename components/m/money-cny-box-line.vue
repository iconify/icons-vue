<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_gde_yhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_gde_yhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:money-cny-box-line" /></template>
