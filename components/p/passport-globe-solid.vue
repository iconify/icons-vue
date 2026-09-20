<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_hy8wbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u_hy8wbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:passport-globe-solid" /></template>
