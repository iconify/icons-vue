<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sizjy_pxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sizjy_pxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:versity" /></template>
