<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaaumybyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="aaaumybyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:task" /></template>
