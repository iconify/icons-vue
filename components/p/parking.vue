<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s015anbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s015anbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:parking" /></template>
