<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-gn4pbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="z-gn4pbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:module-three" /></template>
