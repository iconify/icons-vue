<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_b_x8p1s.css';
import '../../css/a/aiphr2b7y.css';
import '../../css/v/v1hs-27qp.css';
import '../../css/u/u-3sx8b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="t_b_x8p1s"/><circle class="aiphr2b7y"/><circle class="v1hs-27qp"/><path class="u-3sx8b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pest" /></template>
