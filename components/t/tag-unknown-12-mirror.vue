<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz3tp_bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jz3tp_bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:tag-unknown-12-mirror" /></template>
