<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pec648bzl.css';
import '../../css/i/i4lld7tyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pec648bzl"/><path class="i4lld7tyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rupee-20" /></template>
