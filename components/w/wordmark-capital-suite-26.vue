<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu29ecc4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":52,"height":26};
const content = `<path class="nu29ecc4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-capital-suite-26" /></template>
