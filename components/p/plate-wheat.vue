<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkyg6sb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lkyg6sb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plate-wheat" /></template>
