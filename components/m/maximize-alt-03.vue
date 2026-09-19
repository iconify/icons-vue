<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0gdh4bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r0gdh4bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:maximize-alt-03" /></template>
