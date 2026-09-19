<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxj8s_bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxj8s_bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:notice" /></template>
