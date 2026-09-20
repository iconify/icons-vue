<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p392hibyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p392hibyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unwrap-24" /></template>
