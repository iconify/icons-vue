<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjx_55mtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zjx_55mtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:navigation-arrow-on" /></template>
