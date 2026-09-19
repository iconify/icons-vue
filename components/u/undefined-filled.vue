<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1qo09e8y.css';
import '../../css/x/xpcfinb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c1qo09e8y"/><path class="xpcfinb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:undefined-filled" /></template>
