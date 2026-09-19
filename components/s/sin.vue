<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmy8fnbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lmy8fnbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:sin" /></template>
