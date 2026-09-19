<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwx9p0u9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qwx9p0u9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:thinking" /></template>
