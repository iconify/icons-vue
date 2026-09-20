<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y10sehlio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y10sehlio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-pi" /></template>
