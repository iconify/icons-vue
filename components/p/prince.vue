<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/esso3_bvo.css';
import '../../css/h/hdb1zcbyi.css';
import '../../css/n/nu9hkkb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="esso3_bvo"/><path class="hdb1zcbyi"/><path class="nu9hkkb5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:prince" /></template>
