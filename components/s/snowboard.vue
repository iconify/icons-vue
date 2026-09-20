<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b627hbbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="b627hbbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:snowboard" /></template>
