<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju2nyvbsw.css';
import '../../css/a/ac_be7bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ju2nyvbsw"/><path class="ac_be7bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile-download" /></template>
