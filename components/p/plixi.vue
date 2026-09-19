<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsvqpqtgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":488};
const content = `<path class="gsvqpqtgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:plixi" /></template>
