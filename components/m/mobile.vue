<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8sujbo6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="r8sujbo6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mobile" /></template>
