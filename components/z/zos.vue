<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szqt0p1li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="szqt0p1li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zos" /></template>
