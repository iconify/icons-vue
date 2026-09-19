<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leuvwevba.css';
import '../../css/i/i4nfj-f2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="leuvwevba"/><path class="i4nfj-f2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tropical-storm" /></template>
