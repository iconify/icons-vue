<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp_jvhbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp_jvhbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:oval-vertical-filled" /></template>
