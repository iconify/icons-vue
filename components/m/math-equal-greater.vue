<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm9cjfb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm9cjfb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-equal-greater" /></template>
