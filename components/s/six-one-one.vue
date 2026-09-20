<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1p7taciw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f1p7taciw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:six-one-one" /></template>
