<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzrziibvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fzrziibvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:weibo" /></template>
