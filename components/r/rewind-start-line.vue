<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blw-k0btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blw-k0btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rewind-start-line" /></template>
