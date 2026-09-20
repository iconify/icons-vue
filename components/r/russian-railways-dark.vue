<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrb7pj6bi.css';
import '../../css/e/ekdd0gbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":116.5,"height":62.2};
const content = `<path class="lrb7pj6bi"/><path class="ekdd0gbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:russian-railways-dark" /></template>
