<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liowms-cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1728};
const content = `<path class="liowms-cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:wpbeginner" /></template>
