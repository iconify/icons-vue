<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpj6p9orf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":875,"height":2048};
const content = `<path class="tpj6p9orf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:right-double-quote" /></template>
