<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d87tf4g5x.css';
import '../../css/b/btx7j3qro.css';
import '../../css/v/vpayovg2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="d87tf4g5x"/><path class="btx7j3qro"/><path class="vpayovg2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:zip" /></template>
