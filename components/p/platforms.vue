<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q92ghub-h.css';
import '../../css/k/kmch1fxsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q92ghub-h"/><path class="kmch1fxsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:platforms" /></template>
