<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwe_44r1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qwe_44r1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:scope-template" /></template>
