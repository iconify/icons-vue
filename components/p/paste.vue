<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3qj7cccl.css';
import '../../css/q/qwda32bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a3qj7cccl"/><path class="qwda32bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:paste" /></template>
