<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke_8k_97h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke_8k_97h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-to-speech" /></template>
