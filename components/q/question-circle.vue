<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuedu7c-d.css';
import '../../css/j/j84tewqll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kuedu7c-d"/><path class="j84tewqll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:question-circle" /></template>
