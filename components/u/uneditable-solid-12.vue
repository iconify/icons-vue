<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht8bghaxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ht8bghaxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:uneditable-solid-12" /></template>
