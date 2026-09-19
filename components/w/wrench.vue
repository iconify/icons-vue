<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywu73wbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ywu73wbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:wrench" /></template>
