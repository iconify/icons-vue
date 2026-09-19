<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm5zz-bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm5zz-bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plus-sign" /></template>
