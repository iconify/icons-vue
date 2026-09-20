<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7y7bpxwb.css';
import '../../css/u/u53qgwj4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7y7bpxwb"/><path class="u53qgwj4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:tree-fill" /></template>
