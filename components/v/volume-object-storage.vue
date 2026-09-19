<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeqn9cblo.css';
import '../../css/r/rauwxcb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aeqn9cblo"/><path class="rauwxcb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-object-storage" /></template>
