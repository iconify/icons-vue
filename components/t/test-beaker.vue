<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff8_ptq2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ff8_ptq2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:test-beaker" /></template>
