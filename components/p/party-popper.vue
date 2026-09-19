<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh-_mebqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gh-_mebqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:party-popper" /></template>
