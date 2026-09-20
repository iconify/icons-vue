<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa978s6xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-6.5};
const content = `<path class="xa978s6xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:underline" /></template>
