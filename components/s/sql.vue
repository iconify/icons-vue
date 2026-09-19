<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvtjoxbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bvtjoxbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sql" /></template>
