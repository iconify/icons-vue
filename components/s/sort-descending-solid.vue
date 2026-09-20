<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zho1kaciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zho1kaciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sort-descending-solid" /></template>
