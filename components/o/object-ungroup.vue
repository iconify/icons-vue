<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0fnm1bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="w0fnm1bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:object-ungroup" /></template>
