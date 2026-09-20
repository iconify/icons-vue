<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1ckpi3ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1ckpi3ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:music-code" /></template>
