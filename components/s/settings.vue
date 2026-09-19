<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5mm9zbyw.css';
import '../../css/p/phow5bc9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b5mm9zbyw"/><path class="phow5bc9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:settings" /></template>
