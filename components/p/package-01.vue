<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y350s-bsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y350s-bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-01" /></template>
