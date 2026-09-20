<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8v7zs.css';
import '../../css/s/so-from-28.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8v7zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:paint-drop" /></template>
