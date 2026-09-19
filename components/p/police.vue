<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9zji5v_l.css';
import '../../css/s/s8s9ys03v.css';
import '../../css/s/sf_in2t8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c9zji5v_l"/><path class="s8s9ys03v"/><path class="sf_in2t8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:police" /></template>
