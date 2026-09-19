<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0y7ydbid.css';
import '../../css/c/c4j2u85_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i0y7ydbid"/><path class="c4j2u85_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:navaid-seaplane" /></template>
