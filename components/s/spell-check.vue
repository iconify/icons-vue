<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qapn1w99o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qapn1w99o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:spell-check" /></template>
