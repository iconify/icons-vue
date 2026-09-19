<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0v9pbb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t0v9pbb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:video" /></template>
