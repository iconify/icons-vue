<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6u3acbyv.css';
import '../../css/d/d3a2v_bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b6u3acbyv"/><path class="d3a2v_bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:password" /></template>
