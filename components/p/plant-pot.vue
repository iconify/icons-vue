<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx84ycc3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx84ycc3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plant-pot" /></template>
