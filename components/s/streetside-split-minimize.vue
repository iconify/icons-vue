<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfyu9-bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kfyu9-bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:streetside-split-minimize" /></template>
