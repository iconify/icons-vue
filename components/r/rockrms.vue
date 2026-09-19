<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyk16jb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="xyk16jb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:rockrms" /></template>
