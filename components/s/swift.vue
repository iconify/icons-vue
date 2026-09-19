<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyai71m_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wyai71m_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:swift" /></template>
