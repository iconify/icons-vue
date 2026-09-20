<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuhedbkjt.css';
import '../../css/x/x64jix1xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuhedbkjt"/><path class="x64jix1xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:user-arrow-left-filled" /></template>
