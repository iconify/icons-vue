<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpcwetbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpcwetbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:union-solid" /></template>
