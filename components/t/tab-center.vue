<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuqar7t8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kuqar7t8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:tab-center" /></template>
