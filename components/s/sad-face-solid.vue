<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci7n6uvkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ci7n6uvkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sad-face-solid" /></template>
