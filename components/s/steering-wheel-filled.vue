<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_kst0bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b u_kst0bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:steering-wheel-filled" /></template>
