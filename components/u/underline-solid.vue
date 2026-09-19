<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re6h598il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="re6h598il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:underline-solid" /></template>
