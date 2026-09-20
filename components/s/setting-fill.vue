<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n02m407xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n02m407xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:setting-fill" /></template>
