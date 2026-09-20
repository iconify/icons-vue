<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3b5e2bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w3b5e2bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:mood-neutral-solid" /></template>
