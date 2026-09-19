<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erav00b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="erav00b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:volume-1-outline" /></template>
