<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0l0iie8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e0l0iie8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:subtract-1-solid" /></template>
