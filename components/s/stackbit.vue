<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv1sajb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kv1sajb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:stackbit" /></template>
