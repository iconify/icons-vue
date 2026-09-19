<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcd_a183m.css';
import '../../css/j/j4rbxcc2v.css';
import '../../css/h/hmtgkjzwx.css';
import '../../css/b/b9ptyaccn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bcd_a183m"/><path class="j4rbxcc2v"/><path class="hmtgkjzwx"/><path class="b9ptyaccn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:spine-label" /></template>
