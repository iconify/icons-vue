<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eocglkw9k.css';
import '../../css/a/awir01b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eocglkw9k"/><path class="awir01b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:requirement-definition" /></template>
