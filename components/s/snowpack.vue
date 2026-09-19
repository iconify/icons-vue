<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwaz_k85j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pwaz_k85j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:snowpack" /></template>
