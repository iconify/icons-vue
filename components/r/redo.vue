<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pagdp9kcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pagdp9kcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:redo" /></template>
