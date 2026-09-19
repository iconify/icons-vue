<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyj3-clpj.css';
import '../../css/t/tfo6zr1jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyj3-clpj"/><path class="tfo6zr1jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:outdoor-dining" /></template>
