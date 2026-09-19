<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nemeuub4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nemeuub4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ted" /></template>
