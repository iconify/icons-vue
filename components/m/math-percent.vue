<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucwqhuc2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucwqhuc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:math-percent" /></template>
