<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzrg6vbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzrg6vbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star-2-filled" /></template>
