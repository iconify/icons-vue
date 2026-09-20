<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eif-8lxuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eif-8lxuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:park-alt1-15" /></template>
