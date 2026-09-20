<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m45t66w8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m45t66w8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:windows-outline" /></template>
