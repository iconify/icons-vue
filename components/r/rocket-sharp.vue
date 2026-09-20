<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg9g-ctoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg9g-ctoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rocket-sharp" /></template>
