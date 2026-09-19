<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq-zhfbfg.css';
import '../../css/d/did4e-x8k.css';
import '../../css/f/fbylp1beo.css';
import '../../css/v/v29e9xbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sq-zhfbfg"/><path class="did4e-x8k"/><path class="fbylp1beo"/><path class="v29e9xbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:study-transfer" /></template>
