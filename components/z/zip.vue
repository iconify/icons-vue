<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak2v05c1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ak2v05c1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:zip" /></template>
