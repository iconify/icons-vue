<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xru2yjmmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":464};
const content = `<path class="xru2yjmmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:windows" /></template>
