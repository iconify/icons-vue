<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma4-3e-vw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma4-3e-vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:route-fill" /></template>
