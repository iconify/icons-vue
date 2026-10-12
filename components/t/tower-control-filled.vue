<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjr_e6btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjr_e6btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tower-control-filled" /></template>
