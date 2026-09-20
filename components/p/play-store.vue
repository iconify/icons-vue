<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/camcwdxfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="camcwdxfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:play-store" /></template>
