<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nehmr7u7k.css';
import '../../css/d/d1xosacnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="nehmr7u7k"/><path class="d1xosacnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:maltese-cross" /></template>
