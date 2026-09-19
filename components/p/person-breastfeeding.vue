<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at31ysbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="at31ysbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-breastfeeding" /></template>
