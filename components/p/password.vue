<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwbzpyb5i.css';
import '../../css/p/pr_1mzb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wwbzpyb5i"/><circle class="pr_1mzb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:password" /></template>
