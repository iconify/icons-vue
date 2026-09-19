<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kknhpwb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kknhpwb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:vertical-distribute-center" /></template>
