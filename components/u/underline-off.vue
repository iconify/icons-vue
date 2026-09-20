<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4gyvacst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4gyvacst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:underline-off" /></template>
