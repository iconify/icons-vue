<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7z1k8tcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a7z1k8tcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:symbol-male" /></template>
