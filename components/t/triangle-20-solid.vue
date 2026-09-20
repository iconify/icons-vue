<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar9miut_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ar9miut_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:triangle-20-solid" /></template>
