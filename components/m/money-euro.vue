<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b26kolbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="b26kolbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:money-euro" /></template>
