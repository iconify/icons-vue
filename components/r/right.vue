<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg6w1uydn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eg6w1uydn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:right" /></template>
