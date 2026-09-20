<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjgf_ubeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cjgf_ubeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:perl" /></template>
