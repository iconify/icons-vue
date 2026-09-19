<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxoajqbth.css';
import '../../css/o/ov6bxrb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yxoajqbth"/><path class="ov6bxrb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:shapes" /></template>
