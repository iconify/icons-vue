<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/i/i2qezbnqp.css';
import '../../css/w/wj409bb3q.css';
import '../../css/r/r6d918bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(2 2)" class="jtowsomii"><circle class="i2qezbnqp"/><path class="wj409bb3q"/><path class="r6d918bpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:user-male-circle" /></template>
