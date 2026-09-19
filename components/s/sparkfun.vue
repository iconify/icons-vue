<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlv-olo2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xlv-olo2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sparkfun" /></template>
