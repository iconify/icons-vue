<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cie8_kbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cie8_kbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:things" /></template>
