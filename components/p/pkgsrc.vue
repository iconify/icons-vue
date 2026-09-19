<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn86bubkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":487,"height":512};
const content = `<path class="cn86bubkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:pkgsrc" /></template>
