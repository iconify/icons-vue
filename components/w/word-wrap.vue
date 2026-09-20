<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzg8c0oxb.css';
import '../../css/o/ozx0m_bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kzg8c0oxb"/><path class="ozx0m_bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:word-wrap" /></template>
