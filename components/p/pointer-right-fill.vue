<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppxr7-a6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ppxr7-a6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:pointer-right-fill" /></template>
