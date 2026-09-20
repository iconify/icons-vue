<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng5pvcbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ng5pvcbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:shopping-bag-with-exclamation-point" /></template>
