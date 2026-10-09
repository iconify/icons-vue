<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9frzpbrc.css';
import '../../css/m/mtcvrxbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z9frzpbrc"/><path class="mtcvrxbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:video-48" /></template>
