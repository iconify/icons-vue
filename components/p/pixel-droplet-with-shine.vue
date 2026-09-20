<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp6n-mbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lp6n-mbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-droplet-with-shine" /></template>
