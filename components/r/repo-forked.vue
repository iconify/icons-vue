<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cujn-cbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cujn-cbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:repo-forked" /></template>
