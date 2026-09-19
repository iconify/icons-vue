<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uydf_d1if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uydf_d1if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nuxtjs" /></template>
