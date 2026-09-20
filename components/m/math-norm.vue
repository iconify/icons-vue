<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhpwjz4iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhpwjz4iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:math-norm" /></template>
