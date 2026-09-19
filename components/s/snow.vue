<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwg2pfb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kwg2pfb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:snow" /></template>
