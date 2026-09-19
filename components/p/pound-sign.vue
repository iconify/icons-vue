<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttnyopbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="ttnyopbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pound-sign" /></template>
