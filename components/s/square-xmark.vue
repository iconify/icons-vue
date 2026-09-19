<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmr0a4q_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lmr0a4q_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-xmark" /></template>
