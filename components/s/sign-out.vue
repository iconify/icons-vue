<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq0ae0b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bq0ae0b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:sign-out" /></template>
