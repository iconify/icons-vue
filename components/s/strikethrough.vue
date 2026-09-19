<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmoz2bcoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lmoz2bcoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:strikethrough" /></template>
