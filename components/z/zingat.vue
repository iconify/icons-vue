<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b40l44b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b40l44b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:zingat" /></template>
