<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptuvc-bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptuvc-bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sd-card-solid" /></template>
