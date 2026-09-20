<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfp3bzb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zfp3bzb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:smallgear" /></template>
