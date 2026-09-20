<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvo53-bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kvo53-bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:zodiac-9-flat" /></template>
