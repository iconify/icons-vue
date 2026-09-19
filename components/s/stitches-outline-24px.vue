<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehi1ijv8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehi1ijv8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:stitches-outline-24px" /></template>
