<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kva4mxbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kva4mxbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rectangle-line" /></template>
