<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cps6dobbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cps6dobbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sellfy" /></template>
