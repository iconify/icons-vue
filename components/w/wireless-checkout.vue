<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0-6anw0t.css';
import '../../css/j/jr1xz7b-w.css';
import '../../css/l/l2k-wqsww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s0-6anw0t"/><path class="jr1xz7b-w"/><path class="l2k-wqsww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wireless-checkout" /></template>
