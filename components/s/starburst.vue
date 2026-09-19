<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adm1f1rrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="adm1f1rrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:starburst" /></template>
