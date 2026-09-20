<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoys2rbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eoys2rbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:target" /></template>
