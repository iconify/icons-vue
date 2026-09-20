<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3qp_jb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="a3qp_jb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:moon" /></template>
