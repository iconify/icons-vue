<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeipt5bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="eeipt5bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:test-case" /></template>
